<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3v46m1xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r3v46m1xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:displayport-fill" {...props}></Icon>
