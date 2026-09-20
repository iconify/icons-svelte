<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvc5gobpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gvc5gobpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:horizontal-slider-2" {...props}></Icon>
