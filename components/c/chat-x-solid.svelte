<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1quw3brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1quw3brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chat-x-solid" {...props}></Icon>
