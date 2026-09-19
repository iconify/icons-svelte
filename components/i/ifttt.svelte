<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5nny4b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b5nny4b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ifttt" {...props}></Icon>
