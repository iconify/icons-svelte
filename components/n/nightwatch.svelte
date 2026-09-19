<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq8uv6ybu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":423,"height":512};
const content = `<path class="rq8uv6ybu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nightwatch" {...props}></Icon>
