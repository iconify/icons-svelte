<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la--tvb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la--tvb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-vercel-filled" {...props}></Icon>
