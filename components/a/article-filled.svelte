<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-h0x8l3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-h0x8l3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:article-filled" {...props}></Icon>
