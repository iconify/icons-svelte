<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rti4-ty4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rti4-ty4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-long-right" {...props}></Icon>
