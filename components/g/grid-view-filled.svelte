<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_08mbc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_08mbc5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:grid-view-filled" {...props}></Icon>
