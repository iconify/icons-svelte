<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7lin2lzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7lin2lzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:annoyed-sharp" {...props}></Icon>
