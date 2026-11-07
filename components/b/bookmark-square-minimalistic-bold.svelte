<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lybrewbmj.css';
import '../../css/z/zp9omccou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lybrewbmj"/><path class="zp9omccou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-square-minimalistic-bold" {...props}></Icon>
