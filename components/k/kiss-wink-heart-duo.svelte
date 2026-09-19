<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/udfbrio3v.css';
import '../../css/u/uf-kssbkg.css';
import '../../css/w/we8zns5ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="udfbrio3v"/><path class="uf-kssbkg"/><path class="we8zns5ar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kiss-wink-heart-duo" {...props}></Icon>
