<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pze_dub6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pze_dub6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-justified-align-justified-align-alignment-paragraph-formatting-text" {...props}></Icon>
