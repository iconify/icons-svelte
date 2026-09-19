<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsabh2boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xsabh2boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cow-face" {...props}></Icon>
