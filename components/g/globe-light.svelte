<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/e/emrjjuzor.css';
import '../../css/b/bcrcl3pcu.css';
import '../../css/o/oiemdrb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="emrjjuzor"/><path class="bcrcl3pcu"/><path class="oiemdrb8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:globe-light" {...props}></Icon>
