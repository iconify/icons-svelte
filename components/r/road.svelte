<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ibwln3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4ibwln3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:road" {...props}></Icon>
