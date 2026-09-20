<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbej9vbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbej9vbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-arrow-outline" {...props}></Icon>
