<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftk208b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ftk208b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cookie-filled" {...props}></Icon>
