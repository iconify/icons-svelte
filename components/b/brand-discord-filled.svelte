<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg13oeb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg13oeb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-discord-filled" {...props}></Icon>
