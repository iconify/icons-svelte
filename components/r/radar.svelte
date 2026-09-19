<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gztny3bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gztny3bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:radar" {...props}></Icon>
