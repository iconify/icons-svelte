<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i47jo8n6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i47jo8n6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:inbox-alt-filled" {...props}></Icon>
