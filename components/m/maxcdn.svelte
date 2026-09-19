<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6y8ptl6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1760,"height":1280};
const content = `<path class="d6y8ptl6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:maxcdn" {...props}></Icon>
