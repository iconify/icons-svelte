<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_7-lqjyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_7-lqjyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pint-outline" {...props}></Icon>
