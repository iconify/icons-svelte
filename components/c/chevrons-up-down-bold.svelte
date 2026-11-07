<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7lymocvt.css';
import '../../css/g/gx3w35u0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7lymocvt"/><path class="gx3w35u0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-up-down-bold" {...props}></Icon>
