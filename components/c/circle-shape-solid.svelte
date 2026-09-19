<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dblk24e3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dblk24e3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:circle-shape-solid" {...props}></Icon>
