<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhyy4-bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fhyy4-bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:investment-selection-remix" {...props}></Icon>
