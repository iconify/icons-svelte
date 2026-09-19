<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd7pb6bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dd7pb6bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:chrysanthemum-mahjong" {...props}></Icon>
