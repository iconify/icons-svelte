<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf9vpac5p.css';
import '../../css/u/um_zvyb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf9vpac5p"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-close-outline" {...props}></Icon>
