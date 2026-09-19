<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dc2wgbcoh.css';
import '../../css/d/dwf9vmmel.css';
import '../../css/o/our-m0bsu.css';
import '../../css/x/xy3osn-xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dc2wgbcoh"/><path class="dwf9vmmel"/><path class="our-m0bsu"/><path class="xy3osn-xf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:coin-outline" {...props}></Icon>
