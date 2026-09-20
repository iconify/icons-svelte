<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a1p55kjbg.css';
import '../../css/e/e13f8sblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a1p55kjbg"/><path class="e13f8sblt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:building-alt-1-duotone" {...props}></Icon>
