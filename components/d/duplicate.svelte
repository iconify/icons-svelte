<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0jpl0b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c0jpl0b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:duplicate" {...props}></Icon>
