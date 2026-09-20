<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voay2fb_x.css';
import '../../css/r/r4pjpcbzy.css';
import '../../css/h/h5aevgb_l.css';
import '../../css/g/g-sabdtpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="voay2fb_x"/><path class="r4pjpcbzy"/><path class="h5aevgb_l"/><path clip-rule="evenodd" class="g-sabdtpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-wifi-angle-outline" {...props}></Icon>
