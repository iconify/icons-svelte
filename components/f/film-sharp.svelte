<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co4zrkbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co4zrkbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:film-sharp" {...props}></Icon>
