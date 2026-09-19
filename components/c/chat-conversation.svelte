<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkg5m648j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkg5m648j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chat-conversation" {...props}></Icon>
