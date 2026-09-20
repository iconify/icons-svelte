<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d__709b3z.css';
import '../../css/c/c-lbplbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d__709b3z"/><path class="c-lbplbev"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:crop-duotone" {...props}></Icon>
