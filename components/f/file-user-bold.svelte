<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2b6k5bqi.css';
import '../../css/j/j5v3k4mhw.css';
import '../../css/s/se-wl_b4d.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b6k5bqi"/><path class="j5v3k4mhw"/><path clip-rule="evenodd" class="se-wl_b4d"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-user-bold" {...props}></Icon>
