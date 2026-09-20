<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzla5f-tc.css';
import '../../css/g/gw3y6so7m.css';
import '../../css/n/noxr8smkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzla5f-tc"/><path class="gw3y6so7m"/><path class="noxr8smkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rainbow" {...props}></Icon>
