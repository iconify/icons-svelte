<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd2_mcb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd2_mcb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:mortar-board" {...props}></Icon>
