<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_2585bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="r_2585bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:barchartasc" {...props}></Icon>
