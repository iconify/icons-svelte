<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03w44bva.css';
import '../../css/h/hq0wtlbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w03w44bva"/><path class="hq0wtlbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bicycle-wrench" {...props}></Icon>
