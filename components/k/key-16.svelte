<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjppjpbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kjppjpbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:key-16" {...props}></Icon>
