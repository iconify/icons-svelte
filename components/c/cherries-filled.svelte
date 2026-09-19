<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp7dy1b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mp7dy1b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cherries-filled" {...props}></Icon>
