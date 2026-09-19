<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wmbc14diz.css';
import '../../css/e/escw9vdfc.css';
import '../../css/h/hrfy6hbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wmbc14diz"/><path class="escw9vdfc"/><path class="hrfy6hbni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:coins" {...props}></Icon>
