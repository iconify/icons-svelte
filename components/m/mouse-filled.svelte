<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_4iy-3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3_4iy-3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mouse-filled" {...props}></Icon>
