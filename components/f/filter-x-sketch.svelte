<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/he7y-4bpu.css';
import '../../css/a/aolsmqbfe.css';
import '../../css/l/l9srymntf.css';
import '../../css/s/s-m01cccu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="he7y-4bpu"/><path class="aolsmqbfe wm-s"/><path class="l9srymntf wm-k"/><path class="s-m01cccu wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:filter-x-sketch" {...props}></Icon>
