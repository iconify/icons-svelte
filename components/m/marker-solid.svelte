<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw11znqtx.css';
import '../../css/w/wmpwcbcvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw11znqtx"/><path class="wmpwcbcvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:marker-solid" {...props}></Icon>
