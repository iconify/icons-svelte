<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcygz2abe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcygz2abe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cannabis-off-filled" {...props}></Icon>
