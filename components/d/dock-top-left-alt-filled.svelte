<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wopdurd2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wopdurd2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-left-alt-filled" {...props}></Icon>
