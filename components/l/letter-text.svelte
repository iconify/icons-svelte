<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6lz5qbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6lz5qbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-text" {...props}></Icon>
