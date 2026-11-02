<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc55xbcub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc55xbcub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:captions-fill" {...props}></Icon>
