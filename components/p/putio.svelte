<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t4e6ys-el.css';
import '../../css/u/uprcssgre.css';
import '../../css/u/urmk4acde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="t4e6ys-el"/><path clip-rule="evenodd" class="uprcssgre"/><path class="urmk4acde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:putio" {...props}></Icon>
