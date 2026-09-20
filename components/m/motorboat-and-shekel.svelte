<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4j28acah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k4j28acah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-shekel" {...props}></Icon>
