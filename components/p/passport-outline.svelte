<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xwcz-viev.css';
import '../../css/v/vr_ofdcez.css';
import '../../css/e/eudukmbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xwcz-viev"/><path class="vr_ofdcez"/><path clip-rule="evenodd" class="eudukmbaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:passport-outline" {...props}></Icon>
