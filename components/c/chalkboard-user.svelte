<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akho15b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="akho15b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chalkboard-user" {...props}></Icon>
