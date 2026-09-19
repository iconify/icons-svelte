<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h6l7y_btx.css';
import '../../css/i/iuk1pacbe.css';
import '../../css/f/fjq20bbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="h6l7y_btx"/><path class="iuk1pacbe"/><path class="fjq20bbkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:folder-1-duo" {...props}></Icon>
