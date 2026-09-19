<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kb8catbth.css';
import '../../css/i/id1tjk8pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":301,"height":181};
const content = `<g class="ft5dv1b6b"><path class="kb8catbth"/><circle class="id1tjk8pm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cif:bd" {...props}></Icon>
