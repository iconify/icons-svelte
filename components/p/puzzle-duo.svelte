<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gopicnb2u.css';
import '../../css/j/jnn1ze4tr.css';
import '../../css/l/lm81dmcdf.css';
import '../../css/v/v5okizjfs.css';
import '../../css/d/dnbr0rh7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gopicnb2u"/><path class="jnn1ze4tr"/><path class="lm81dmcdf"/><path class="v5okizjfs"/><path class="dnbr0rh7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:puzzle-duo" {...props}></Icon>
