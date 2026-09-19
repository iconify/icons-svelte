<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c17kk1-8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c17kk1-8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:joystick" {...props}></Icon>
