<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz4pkpnup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz4pkpnup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:discord-fill" {...props}></Icon>
