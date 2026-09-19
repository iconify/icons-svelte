<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbyvz2pfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbyvz2pfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-bubble-empty-solid" {...props}></Icon>
