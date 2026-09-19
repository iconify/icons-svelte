<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c787b-zxi.css';
import '../../css/b/bxutvf4dz.css';
import '../../css/v/v62_33uqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="c787b-zxi"/><path class="bxutvf4dz"/><path class="v62_33uqe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bucket" {...props}></Icon>
