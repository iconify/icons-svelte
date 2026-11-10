<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s56hofbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s56hofbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-pop-with-bite" {...props}></Icon>
