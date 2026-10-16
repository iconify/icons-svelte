<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p480i1bck.css';
import '../../css/c/c9n0mybal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p480i1bck"/><path class="c9n0mybal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ear-defenders-20-bold" {...props}></Icon>
