<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szvseab6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szvseab6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:extension-filled" {...props}></Icon>
