<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7a3s1b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7a3s1b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-sparkles-solid" {...props}></Icon>
