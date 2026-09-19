<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju1-0mb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ju1-0mb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:code-pull-request" {...props}></Icon>
