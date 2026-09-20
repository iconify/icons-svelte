<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z6bk53brd.css';
import '../../css/a/ab_ydd6ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":950,"height":260.203};
const content = `<g class="ft5dv1b6b"><path class="z6bk53brd"/><path class="ab_ydd6ir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reuters" {...props}></Icon>
