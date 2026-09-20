<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu5306mfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bu5306mfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-call-bold" {...props}></Icon>
