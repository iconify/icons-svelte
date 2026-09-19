<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9k189_9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t9k189_9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face2-filled" {...props}></Icon>
