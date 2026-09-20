<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaf_pfb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaf_pfb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-heart-outline" {...props}></Icon>
