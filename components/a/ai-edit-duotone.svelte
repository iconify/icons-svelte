<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i7_llabwm.css';
import '../../css/q/qh4ywac4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i7_llabwm"/><path class="qh4ywac4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-edit-duotone" {...props}></Icon>
