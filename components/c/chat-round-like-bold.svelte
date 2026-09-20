<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwx4n85mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zwx4n85mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-like-bold" {...props}></Icon>
