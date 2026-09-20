<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl818kyew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl818kyew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:helm-dark" {...props}></Icon>
