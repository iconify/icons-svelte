<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyezjvb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="lyezjvb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:paint-11" {...props}></Icon>
