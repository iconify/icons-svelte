<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b34y5p2yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b34y5p2yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:green-dragon-mahjong" {...props}></Icon>
