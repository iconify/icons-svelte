<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/gz3sv5byc.css';
import '../../css/u/ubyycbaxw.css';
import '../../css/z/zzhwb5nor.css';
import '../../css/u/uvgh2l5nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="gz3sv5byc wm-shadow"/><path class="ubyycbaxw"/><path class="zzhwb5nor"/><path class="uvgh2l5nr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:avatar-robot" {...props}></Icon>
