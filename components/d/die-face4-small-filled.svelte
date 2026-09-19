<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgmu_kbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mgmu_kbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face4-small-filled" {...props}></Icon>
