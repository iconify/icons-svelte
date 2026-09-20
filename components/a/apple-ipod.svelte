<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz0z2xbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz0z2xbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:apple-ipod" {...props}></Icon>
