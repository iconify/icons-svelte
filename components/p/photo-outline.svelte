<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/vl_s_18va.css';
import '../../css/p/ph-ksgbhf.css';
import '../../css/z/zfkgdttpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="vl_s_18va"/><circle class="ph-ksgbhf"/><path class="zfkgdttpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:photo-outline" {...props}></Icon>
