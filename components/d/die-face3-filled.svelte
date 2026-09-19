<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0uqw6imm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j0uqw6imm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face3-filled" {...props}></Icon>
