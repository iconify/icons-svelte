<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7haebbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="u7haebbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:paper-tablet" {...props}></Icon>
