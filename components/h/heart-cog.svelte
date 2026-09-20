<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwff-u_lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwff-u_lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-cog" {...props}></Icon>
