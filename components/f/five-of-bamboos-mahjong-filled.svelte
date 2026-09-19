<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxq1d5bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sxq1d5bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:five-of-bamboos-mahjong-filled" {...props}></Icon>
