<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs1c3lqko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":472};
const content = `<path class="vs1c3lqko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:important" {...props}></Icon>
