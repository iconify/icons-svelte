<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlaz4-4se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rlaz4-4se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-fill-16" {...props}></Icon>
