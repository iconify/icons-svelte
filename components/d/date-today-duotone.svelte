<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/be0ma7bmn.css';
import '../../css/k/ktzs39bmv.css';
import '../../css/x/x1wlzug7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="be0ma7bmn"/><path class="ktzs39bmv"/><path class="x1wlzug7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:date-today-duotone" {...props}></Icon>
