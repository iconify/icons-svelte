<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv_hpvbul.css';
import '../../css/c/cv8_uxbtz.css';
import '../../css/t/tznmijrmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="kv_hpvbul"><path class="cv8_uxbtz"/><path class="tznmijrmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dreammachine-luma" {...props}></Icon>
