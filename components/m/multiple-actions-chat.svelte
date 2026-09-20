<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx7nithiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx7nithiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:multiple-actions-chat" {...props}></Icon>
