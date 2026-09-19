<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2lnh2bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="d2lnh2bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:four-of-bamboos-mahjong" {...props}></Icon>
