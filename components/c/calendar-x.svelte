<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/p/p9ypwgl8j.css';
import '../../css/n/n5fs7xbcj.css';
import '../../css/j/jmvv3kbnk.css';
import '../../css/h/hp_yrebrn.css';
import '../../css/i/i1g1qkwrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="p9ypwgl8j"/><path class="n5fs7xbcj wm-shine"/><path class="jmvv3kbnk wm-k"/><path class="hp_yrebrn wm-a"/><path class="i1g1qkwrt wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:calendar-x" {...props}></Icon>
