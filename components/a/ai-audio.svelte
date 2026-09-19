<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/ffr29_hhx.css';
import '../../css/d/dg7qrmb6g.css';
import '../../css/u/u3714py3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ffr29_hhx"/><path class="dg7qrmb6g"/><path class="u3714py3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-audio" {...props}></Icon>
