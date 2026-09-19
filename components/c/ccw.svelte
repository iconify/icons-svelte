<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vik6htbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vik6htbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:ccw" {...props}></Icon>
