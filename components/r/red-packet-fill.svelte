<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgoo71jhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgoo71jhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:red-packet-fill" {...props}></Icon>
