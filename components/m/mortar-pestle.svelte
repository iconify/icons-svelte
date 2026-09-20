<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4f0s_zex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p4f0s_zex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mortar-pestle" {...props}></Icon>
