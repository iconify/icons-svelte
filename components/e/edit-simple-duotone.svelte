<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oh8gi2b2u.css';
import '../../css/p/p3bvlbtrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oh8gi2b2u"/><path class="p3bvlbtrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:edit-simple-duotone" {...props}></Icon>
