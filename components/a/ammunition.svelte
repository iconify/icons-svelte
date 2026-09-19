<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhp2b6bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhp2b6bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ammunition" {...props}></Icon>
