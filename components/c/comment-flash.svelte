<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkp47mbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkp47mbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-flash" {...props}></Icon>
