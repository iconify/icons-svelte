<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f4omlmbfc.css';
import '../../css/w/w2abumm4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f4omlmbfc"/><path class="w2abumm4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:briefcases-duotone" {...props}></Icon>
