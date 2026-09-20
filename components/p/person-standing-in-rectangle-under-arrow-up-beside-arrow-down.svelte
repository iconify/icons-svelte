<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g25ne3b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g25ne3b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-in-rectangle-under-arrow-up-beside-arrow-down" {...props}></Icon>
