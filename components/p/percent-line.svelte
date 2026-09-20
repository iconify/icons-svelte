<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/amxs67rqb.css';
import '../../css/p/pm27xrbad.css';
import '../../css/j/j_dnqlc5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amxs67rqb"/><circle class="pm27xrbad"/><circle class="j_dnqlc5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:percent-line" {...props}></Icon>
