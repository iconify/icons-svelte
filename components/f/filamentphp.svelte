<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_v47x3vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j_v47x3vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:filamentphp" {...props}></Icon>
