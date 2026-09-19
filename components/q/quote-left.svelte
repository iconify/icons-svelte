<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md8i9fb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md8i9fb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:quote-left" {...props}></Icon>
