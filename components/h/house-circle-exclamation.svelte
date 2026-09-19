<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2gh_abbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r2gh_abbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-circle-exclamation" {...props}></Icon>
