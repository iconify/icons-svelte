<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kotm7ebod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kotm7ebod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chat-bot-solid" {...props}></Icon>
