<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6j-j1bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":472};
const content = `<path class="t6j-j1bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:apps" {...props}></Icon>
