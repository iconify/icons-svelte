<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up41n5_fe.css';
import '../../css/y/yb5y__l1h.css';
import '../../css/x/x8dhmccog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="up41n5_fe"/><path class="yb5y__l1h"/><path class="x8dhmccog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-electron-outline" {...props}></Icon>
