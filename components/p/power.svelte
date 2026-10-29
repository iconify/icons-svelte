<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdgbhdbzt.css';
import '../../css/p/pla9akn6j.css';
import '../../css/x/xwbt8jbcw.css';
import '../../css/m/m7dz4xbax.css';
import '../../css/f/flagi397l.css';
import '../../css/d/drotr3gay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdgbhdbzt wm-shadow"/><path class="pla9akn6j wm-k"/><path class="wm-k xwbt8jbcw"/><path class="m7dz4xbax wm-k"/><path class="flagi397l wm-k"/><path class="drotr3gay wm-shine"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:power" {...props}></Icon>
