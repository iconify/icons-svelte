<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zmnjdabrt.css';
import '../../css/l/lyr4a7bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zmnjdabrt"/><path class="lyr4a7bbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-circle-duotone" {...props}></Icon>
