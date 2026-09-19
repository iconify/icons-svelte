<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms98do_7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ms98do_7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:comment-slash" {...props}></Icon>
