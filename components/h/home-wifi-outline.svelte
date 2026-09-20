<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voay2fb_x.css';
import '../../css/l/l-hb7_w0z.css';
import '../../css/h/h5aevgb_l.css';
import '../../css/m/mjh1mwb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voay2fb_x"/><path class="l-hb7_w0z"/><path class="h5aevgb_l"/><path clip-rule="evenodd" class="mjh1mwb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-wifi-outline" {...props}></Icon>
