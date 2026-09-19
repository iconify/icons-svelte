<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4q0bc4lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="j4q0bc4lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:itunes" {...props}></Icon>
