<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu6gvgk1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vu6gvgk1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face1-small-filled" {...props}></Icon>
