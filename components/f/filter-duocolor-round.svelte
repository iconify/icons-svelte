<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxhjpia-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxhjpia-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:filter-duocolor-round" {...props}></Icon>
