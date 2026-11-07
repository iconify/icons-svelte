<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-d1zfbuf.css';
import '../../css/w/wa25nab9h.css';
import '../../css/c/cj64798lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-d1zfbuf"/><path class="wa25nab9h"/><path class="cj64798lz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-2-line-duotone" {...props}></Icon>
