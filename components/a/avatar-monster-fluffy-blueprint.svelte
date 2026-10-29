<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/f/fgaqfsbrg.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/r/rweozib1u.css';
import '../../css/x/x5kvoacvm.css';
import '../../css/x/x82fbcc8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="fgaqfsbrg wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="rweozib1u wm-k"/><path class="wm-a x5kvoacvm"/><path class="wm-k x82fbcc8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-monster-fluffy-blueprint" {...props}></Icon>
