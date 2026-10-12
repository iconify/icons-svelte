<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocp-zwjse.css';
import '../../css/z/znuj7bbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ocp-zwjse"/><path class="znuj7bbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-arrow-left-stroke-20" {...props}></Icon>
