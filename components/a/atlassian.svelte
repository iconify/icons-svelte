<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm55zv6ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sm55zv6ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:atlassian" {...props}></Icon>
