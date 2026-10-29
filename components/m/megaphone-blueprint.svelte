<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/m/mze3curll.css';
import '../../css/d/d17zgng_a.css';
import '../../css/z/z43j8q9jh.css';
import '../../css/u/uvfwd4wqi.css';
import '../../css/f/f26bn-hui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="mze3curll wm-deco"/><path class="d17zgng_a wm-deco"/><path class="wm-deco z43j8q9jh"/><path class="uvfwd4wqi wm-k"/><path class="f26bn-hui wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:megaphone-blueprint" {...props}></Icon>
