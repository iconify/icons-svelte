<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvw60zv3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvw60zv3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-html" {...props}></Icon>
