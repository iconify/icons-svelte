<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyh_xgu6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fyh_xgu6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-money-outline" {...props}></Icon>
