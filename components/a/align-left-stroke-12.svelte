<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1coyp5mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e1coyp5mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-left-stroke-12" {...props}></Icon>
