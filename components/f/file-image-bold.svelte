<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goaxqgbme.css';
import '../../css/q/qpih9sbik.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goaxqgbme"/><path class="qpih9sbik"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-image-bold" {...props}></Icon>
