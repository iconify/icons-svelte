<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fkfoqunaf.css';
import '../../css/i/i-58-uedr.css';
import '../../css/l/l7ja-xnch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fkfoqunaf"/><path class="i-58-uedr wm-k"/><path class="l7ja-xnch wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:locate-fixed-sketch" {...props}></Icon>
