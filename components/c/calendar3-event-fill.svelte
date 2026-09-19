<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3r0drnxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q3r0drnxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar3-event-fill" {...props}></Icon>
