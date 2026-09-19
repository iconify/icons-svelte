<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipfdw6b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ipfdw6b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-grin-stars" {...props}></Icon>
