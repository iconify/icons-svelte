<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pib3_sb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pib3_sb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:join-straight" {...props}></Icon>
