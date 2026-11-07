<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n49uhib3z.css';
import '../../css/s/siai_tb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n49uhib3z"/><path class="siai_tb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-unread-bold" {...props}></Icon>
