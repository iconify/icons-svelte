<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0kp65hhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x0kp65hhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:flask-florence" {...props}></Icon>
