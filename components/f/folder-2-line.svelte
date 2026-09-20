<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-lknbcau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-lknbcau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-2-line" {...props}></Icon>
