<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-30mbjbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f-30mbjbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-calt" {...props}></Icon>
