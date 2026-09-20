<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giqwm_2jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="giqwm_2jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-rocketship" {...props}></Icon>
