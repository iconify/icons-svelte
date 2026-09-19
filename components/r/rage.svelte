<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gshe_di8n.css';
import '../../css/t/tcsfyac_a.css';
import '../../css/f/fb_ijtbgm.css';
import '../../css/z/z7iigyukn.css';
import '../../css/w/wlzju0bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gshe_di8n"/><path class="tcsfyac_a"/><path class="fb_ijtbgm"/><path class="z7iigyukn"/><path class="wlzju0bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rage" {...props}></Icon>
