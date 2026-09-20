<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvyr4dczo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fvyr4dczo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:quotation-2" {...props}></Icon>
