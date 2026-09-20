<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kt1ahab5v.css';
import '../../css/a/adlaw-b6t.css';
import '../../css/o/onymejbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kt1ahab5v"/><path class="adlaw-b6t"/><path class="onymejbgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diskette-broken" {...props}></Icon>
