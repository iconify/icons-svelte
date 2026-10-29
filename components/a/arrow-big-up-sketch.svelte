<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o_vht2jmm.css';
import '../../css/b/bxecxbb3f.css';
import '../../css/m/mcsf3nhcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o_vht2jmm"/><path class="bxecxbb3f"/><path class="mcsf3nhcs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-big-up-sketch" {...props}></Icon>
