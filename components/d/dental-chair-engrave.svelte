<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/k5dkv5b0m.css';
import '../../css/u/uke6w0b1s.css';
import '../../css/c/c7nk0cb5w.css';
import '../../css/m/mv4mpebft.css';
import '../../css/i/i0a_nyk6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="k5dkv5b0m wm-k"/><path class="uke6w0b1s wm-a"/><path class="c7nk0cb5w wm-shadow"/><path class="mv4mpebft wm-k"/><path class="i0a_nyk6o wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dental-chair-engrave" {...props}></Icon>
