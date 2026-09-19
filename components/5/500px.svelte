<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaqj09b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="aaqj09b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:500px" {...props}></Icon>
