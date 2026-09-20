<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tr_5cybnu.css';
import '../../css/k/kbiba4bgc.css';
import '../../css/a/an4w8gbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tr_5cybnu"/><path class="kbiba4bgc"/><circle class="an4w8gbhl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-marker-area-line" {...props}></Icon>
