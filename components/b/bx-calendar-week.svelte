<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7z0xbvn.css';
import '../../css/f/fxr_yobjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7z0xbvn"/><path class="fxr_yobjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-calendar-week" {...props}></Icon>
