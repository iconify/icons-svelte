<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsu8t_9kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsu8t_9kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-heart-solid" {...props}></Icon>
