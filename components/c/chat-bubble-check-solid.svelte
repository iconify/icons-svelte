<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke7794biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ke7794biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-bubble-check-solid" {...props}></Icon>
