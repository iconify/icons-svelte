<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdi_z7bbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdi_z7bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-square-bold" {...props}></Icon>
