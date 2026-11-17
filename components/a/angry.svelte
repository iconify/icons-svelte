<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/f/f_362pbxn.css';
import '../../css/z/zolwr1t2h.css';
import '../../css/m/mj4zh1bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="f_362pbxn"/><path class="zolwr1t2h"/><path class="mj4zh1bkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:angry" {...props}></Icon>
