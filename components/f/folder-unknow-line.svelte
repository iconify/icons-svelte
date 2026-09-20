<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prht9cg7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prht9cg7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-unknow-line" {...props}></Icon>
