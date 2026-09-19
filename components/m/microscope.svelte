<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/uznrkyg-i.css';
import '../../css/w/wwhz16b1f.css';
import '../../css/n/n3l509bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uznrkyg-i"/><path class="wwhz16b1f"/><path class="n3l509bcp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:microscope" {...props}></Icon>
