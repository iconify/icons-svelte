<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfsfc7bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfsfc7bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ice-cream-2" {...props}></Icon>
