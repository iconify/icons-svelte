<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm7kl-mmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tm7kl-mmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-takeoff" {...props}></Icon>
