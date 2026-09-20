<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6rjw2b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="w6rjw2b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:arrow-bottom-left" {...props}></Icon>
