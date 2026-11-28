<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxbs1bui.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/u/udyesyb8b.css';
import '../../css/b/bcygd8z2n.css';
import '../../css/j/jbduwq09o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psxbs1bui secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="udyesyb8b"/><path class="bcygd8z2n"/><path class="jbduwq09o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-swiss-franc-duo" {...props}></Icon>
