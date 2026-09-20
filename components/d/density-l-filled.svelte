<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns3wwebbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ns3wwebbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:density-l-filled" {...props}></Icon>
