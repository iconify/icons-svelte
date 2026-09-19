<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-9ok0b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j-9ok0b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-scissors-filled" {...props}></Icon>
