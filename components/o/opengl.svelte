<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpvhkib2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpvhkib2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:opengl" {...props}></Icon>
