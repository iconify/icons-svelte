<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cftt4jdtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cftt4jdtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:last-quarter-moon-symbol" {...props}></Icon>
