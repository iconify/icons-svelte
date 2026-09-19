<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj5lm6beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xj5lm6beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:planet" {...props}></Icon>
