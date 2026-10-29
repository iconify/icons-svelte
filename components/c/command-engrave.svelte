<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gycplyitt.css';
import '../../css/s/snq7lfbcd.css';
import '../../css/t/t83hz6hkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gycplyitt"/><path class="snq7lfbcd wm-shadow"/><path class="t83hz6hkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:command-engrave" {...props}></Icon>
