<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mffzdkbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mffzdkbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-graphics-filled" {...props}></Icon>
