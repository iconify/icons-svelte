<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a60ncdcxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a60ncdcxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:five-of-characters-mahjong" {...props}></Icon>
