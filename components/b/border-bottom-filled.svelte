<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl5_it4ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl5_it4ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-bottom-filled" {...props}></Icon>
