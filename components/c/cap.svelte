<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/ob3u8h07i.css';
import '../../css/x/xpnycobrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ob3u8h07i"/><path class="xpnycobrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cap" {...props}></Icon>
