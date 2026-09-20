<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwico__yj.css';
import '../../css/h/htu6zoakn.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/u/usozxnbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGREWbgcXm" class="jwico__yj"/></defs><circle class="htu6zoakn"/><use href="#SVGREWbgcXm"/><g class="kdz4acc8r"><circle class="usozxnbrm"/><use href="#SVGREWbgcXm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:regional-indicator-j" {...props}></Icon>
