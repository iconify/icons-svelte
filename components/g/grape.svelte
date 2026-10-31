<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/w/w9rkhebuc.css';
import '../../css/m/mg70k78il.css';
import '../../css/l/lhyb3bbbn.css';
import '../../css/x/x2f5ebbeb.css';
import '../../css/p/pfiv80a5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="w9rkhebuc"/><path class="mg70k78il wm-shine"/><path class="lhyb3bbbn wm-k"/><path class="wm-a x2f5ebbeb"/><path class="pfiv80a5u wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:grape" {...props}></Icon>
