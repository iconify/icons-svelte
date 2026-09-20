<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onbda0s6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="onbda0s6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:led" {...props}></Icon>
