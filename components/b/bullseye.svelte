<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo5bo8b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo5bo8b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bullseye" {...props}></Icon>
