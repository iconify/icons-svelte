<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr85l6q2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vr85l6q2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cursor" {...props}></Icon>
