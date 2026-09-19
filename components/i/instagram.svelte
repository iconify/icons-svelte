<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jovuhgg2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jovuhgg2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:instagram" {...props}></Icon>
