<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh0xbabcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh0xbabcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bag-personal-tag-outline" {...props}></Icon>
