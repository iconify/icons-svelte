<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-9r5omfu.css';
import '../../css/v/vxwsbfy9u.css';
import '../../css/n/ngn3wxxwh.css';
import '../../css/z/zi89txbue.css';
import '../../css/l/l2sfx3bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-9r5omfu"/><path class="vxwsbfy9u"/><path class="ngn3wxxwh"/><path class="zi89txbue"/><path class="l2sfx3bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-paw" {...props}></Icon>
