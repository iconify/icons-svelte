<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rep-qbcvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rep-qbcvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:orthogon7x7" {...props}></Icon>
