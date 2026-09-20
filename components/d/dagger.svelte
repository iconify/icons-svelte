<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taw1387fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="taw1387fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:dagger" {...props}></Icon>
