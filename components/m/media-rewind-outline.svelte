<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8_jxdgwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8_jxdgwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:media-rewind-outline" {...props}></Icon>
