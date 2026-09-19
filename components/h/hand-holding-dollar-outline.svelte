<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/ba5fcebjo.css';
import '../../css/t/t71e3kbgv.css';
import '../../css/a/afkng-bck.css';
import '../../css/i/inuhyfbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ba5fcebjo"/><path clip-rule="evenodd" class="t71e3kbgv"/><path class="afkng-bck"/><path clip-rule="evenodd" class="inuhyfbds"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-dollar-outline" {...props}></Icon>
