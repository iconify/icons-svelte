<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zgcba5bww.css';
import '../../css/n/nk1speb3h.css';
import '../../css/f/ffrnjebod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zgcba5bww"/><path class="nk1speb3h"/><path class="ffrnjebod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:dictionary-language-book-flat" {...props}></Icon>
