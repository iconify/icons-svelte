<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d57gu2bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d57gu2bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-cog" {...props}></Icon>
