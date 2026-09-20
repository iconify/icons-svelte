<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy2w6dp5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy2w6dp5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-down" {...props}></Icon>
