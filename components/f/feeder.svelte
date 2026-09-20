<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byi03x_hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="byi03x_hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:feeder" {...props}></Icon>
