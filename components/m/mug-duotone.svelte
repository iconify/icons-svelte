<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ygr4kzk5x.css';
import '../../css/w/wbvi0ucwi.css';
import '../../css/v/vg6w0cbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ygr4kzk5x"/><path clip-rule="evenodd" class="wbvi0ucwi"/><path class="vg6w0cbcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mug-duotone" {...props}></Icon>
