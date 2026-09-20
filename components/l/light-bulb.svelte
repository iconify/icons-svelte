<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfnw5t5bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="tfnw5t5bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:light-bulb" {...props}></Icon>
