<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/iac4ogb3m.css';
import '../../css/x/xnv84xb3j.css';
import '../../css/r/r9qrt2bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iac4ogb3m"/><path class="xnv84xb3j"/><path class="r9qrt2bvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:glasses-sun" {...props}></Icon>
