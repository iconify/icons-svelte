<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxgx5bc6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vxgx5bc6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:circle-duo" {...props}></Icon>
