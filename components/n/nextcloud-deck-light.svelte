<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm066d1jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tm066d1jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-deck-light" {...props}></Icon>
