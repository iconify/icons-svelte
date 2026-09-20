<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om5-2ls3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om5-2ls3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cloud-off-line" {...props}></Icon>
