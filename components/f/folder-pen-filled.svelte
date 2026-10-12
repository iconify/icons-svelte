<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc1up6d3b.css';
import '../../css/r/rpiivsbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc1up6d3b"/><path class="rpiivsbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-pen-filled" {...props}></Icon>
