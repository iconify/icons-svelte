<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5y4xbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd5y4xbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:more-menu-vertical-line" {...props}></Icon>
