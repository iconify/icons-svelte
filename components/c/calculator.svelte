<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkaz_ncxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="tkaz_ncxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:calculator" {...props}></Icon>
