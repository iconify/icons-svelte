<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdi4gp9eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdi4gp9eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-info-filled" {...props}></Icon>
