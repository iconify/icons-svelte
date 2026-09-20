<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttdwrtber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ttdwrtber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-right-align-rag-paragraph-text-alignment-align-right-formatting-left" {...props}></Icon>
