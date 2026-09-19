<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t7mv73bbb.css';
import '../../css/i/izhj-bbzf.css';
import '../../css/i/i-6_bgbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t7mv73bbb"/><path class="izhj-bbzf"/><path class="i-6_bgbnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:picture-in-picture-on" {...props}></Icon>
