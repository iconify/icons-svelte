<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk2-5bcxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk2-5bcxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:chat-lines-solid" {...props}></Icon>
