<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgku137fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgku137fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-off-solid" {...props}></Icon>
