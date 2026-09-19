<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y28ds_u5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="y28ds_u5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:four-duo" {...props}></Icon>
