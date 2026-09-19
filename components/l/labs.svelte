<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nu7yhz69s.css';
import '../../css/u/u_3sxfbdf.css';
import '../../css/i/icc58_d8i.css';
import '../../css/e/e2j9ewbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nu7yhz69s"/><path class="u_3sxfbdf"/><path class="icc58_d8i"/><path class="e2j9ewbwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:labs" {...props}></Icon>
