<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zmnjdabrt.css';
import '../../css/u/ue8wqn48z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zmnjdabrt"/><path class="ue8wqn48z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:download-offline-duotone" {...props}></Icon>
