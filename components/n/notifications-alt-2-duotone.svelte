<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wc_tf6b1e.css';
import '../../css/f/f2b0kpbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wc_tf6b1e"/><path class="f2b0kpbem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-alt-2-duotone" {...props}></Icon>
