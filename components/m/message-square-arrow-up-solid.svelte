<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq6ply3up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq6ply3up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-arrow-up-solid" {...props}></Icon>
