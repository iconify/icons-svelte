<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh9-u_epy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oh9-u_epy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-textcolor" {...props}></Icon>
