<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljio3duaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljio3duaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chat-cancel" {...props}></Icon>
