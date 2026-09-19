<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffmwi4b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ffmwi4b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-han" {...props}></Icon>
