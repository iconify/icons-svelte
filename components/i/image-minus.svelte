<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kzmnvikyr.css';
import '../../css/k/kaaj88bma.css';
import '../../css/k/kiwzkfnae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kzmnvikyr"/><path clip-rule="evenodd" class="kaaj88bma"/><path class="kiwzkfnae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:image-minus" {...props}></Icon>
