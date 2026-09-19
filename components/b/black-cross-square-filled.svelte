<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5tnxjw_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q5tnxjw_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-cross-square-filled" {...props}></Icon>
