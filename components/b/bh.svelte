<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f7hinzb1w.css';
import '../../css/g/g1myj0bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":181};
const content = `<g class="ft5dv1b6b"><path class="f7hinzb1w"/><path class="g1myj0bgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:bh" {...props}></Icon>
