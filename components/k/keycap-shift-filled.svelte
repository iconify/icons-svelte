<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgajd6j3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fgajd6j3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-shift-filled" {...props}></Icon>
