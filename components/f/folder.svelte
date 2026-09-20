<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thdeo9zrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thdeo9zrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:folder" {...props}></Icon>
