<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s25wggbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s25wggbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextdns-light" {...props}></Icon>
