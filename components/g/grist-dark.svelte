<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8eptqggo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u8eptqggo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grist-dark" {...props}></Icon>
