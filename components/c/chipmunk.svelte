<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywu4_4b-u.css';
import '../../css/m/me6xtzbri.css';
import '../../css/z/z3fiy1goj.css';
import '../../css/x/x_umbtwhv.css';
import '../../css/i/ijtms13ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywu4_4b-u"/><path class="me6xtzbri"/><path class="z3fiy1goj"/><path class="x_umbtwhv"/><path class="ijtms13ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:chipmunk" {...props}></Icon>
