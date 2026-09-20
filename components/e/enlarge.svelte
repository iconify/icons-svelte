<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgwkk1peg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cgwkk1peg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:enlarge" {...props}></Icon>
