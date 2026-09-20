<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tken0i2np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tken0i2np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-right-down" {...props}></Icon>
