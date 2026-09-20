<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/h/hkp8nlzop.css';
import '../../css/l/l78etzbyf.css';
import '../../css/k/krfa7cniv.css';
import '../../css/t/tzdrbr9zn.css';
import '../../css/g/graxhiypk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="hkp8nlzop"/><path class="l78etzbyf"/><path class="krfa7cniv"/><path class="tzdrbr9zn"/><path class="graxhiypk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-shopping-logo" {...props}></Icon>
