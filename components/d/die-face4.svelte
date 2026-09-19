<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uonzi7l5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uonzi7l5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face4" {...props}></Icon>
