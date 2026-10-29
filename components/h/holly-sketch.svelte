<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cvk1ilb9q.css';
import '../../css/g/gkeixvvic.css';
import '../../css/c/cpnpjfb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cvk1ilb9q wm-k"/><path class="gkeixvvic wm-k"/><path class="cpnpjfb3t wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:holly-sketch" {...props}></Icon>
