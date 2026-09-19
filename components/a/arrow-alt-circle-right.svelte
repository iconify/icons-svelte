<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuq6-10mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wuq6-10mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:arrow-alt-circle-right" {...props}></Icon>
