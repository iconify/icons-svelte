<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyk45popi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nyk45popi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ohio-with-capital-star" {...props}></Icon>
