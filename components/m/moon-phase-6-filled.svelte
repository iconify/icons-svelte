<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le_b2hb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le_b2hb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-phase-6-filled" {...props}></Icon>
