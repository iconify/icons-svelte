<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7xpn6j1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h7xpn6j1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:properties" {...props}></Icon>
