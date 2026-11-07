<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpppxlokg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpppxlokg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-broken" {...props}></Icon>
