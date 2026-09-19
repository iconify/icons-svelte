<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co_jnenov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co_jnenov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:laptop-sharp" {...props}></Icon>
