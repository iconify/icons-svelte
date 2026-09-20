<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd4x_8b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="rd4x_8b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mention" {...props}></Icon>
