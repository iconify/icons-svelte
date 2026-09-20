<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/x/xe28qbbib.css';
import '../../css/f/f4f9qlbwy.css';
import '../../css/a/an94kvrfr.css';
import '../../css/o/og_9js9al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xe28qbbib"/><path class="f4f9qlbwy"/><circle class="an94kvrfr"/><circle class="og_9js9al"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:hand-coins" {...props}></Icon>
