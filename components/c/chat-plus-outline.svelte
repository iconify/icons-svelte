<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huer_3mri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huer_3mri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-plus-outline" {...props}></Icon>
