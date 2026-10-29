<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyo0a_ipl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyo0a_ipl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grid-2x2-solid" {...props}></Icon>
