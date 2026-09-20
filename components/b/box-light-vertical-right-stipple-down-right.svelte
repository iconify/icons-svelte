<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyt5_xbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="vyt5_xbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-right-stipple-down-right" {...props}></Icon>
