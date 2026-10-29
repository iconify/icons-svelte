<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ibx4phblj.css';
import '../../css/r/rweeoebtw.css';
import '../../css/k/kx5befbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ibx4phblj"/><path class="rweeoebtw"/><path class="kx5befbjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:music-note-sketch" {...props}></Icon>
