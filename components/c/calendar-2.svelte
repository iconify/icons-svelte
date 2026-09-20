<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bmynvddub.css';
import '../../css/p/pec-oacye.css';
import '../../css/u/uc2g8vpel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmynvddub"/><path class="pec-oacye"/><path class="uc2g8vpel"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:calendar-2" {...props}></Icon>
