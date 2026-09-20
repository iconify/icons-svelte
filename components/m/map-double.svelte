<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cgnv8ebcv.css';
import '../../css/r/rrkrpelya.css';
import '../../css/p/ptym6unom.css';
import '../../css/o/okygb9b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cgnv8ebcv"/><path class="rrkrpelya"/><path class="ptym6unom"/><path class="okygb9b9t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-double" {...props}></Icon>
