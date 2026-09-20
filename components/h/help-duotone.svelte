<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zmnjdabrt.css';
import '../../css/n/ne_k8y95s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zmnjdabrt"/><path class="ne_k8y95s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:help-duotone" {...props}></Icon>
