<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu88yodte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="zu88yodte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:reply-all" {...props}></Icon>
