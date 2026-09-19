<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc3l9v3wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bc3l9v3wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:megaphone" {...props}></Icon>
