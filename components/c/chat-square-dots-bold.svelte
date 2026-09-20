<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpe488jpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpe488jpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-dots-bold" {...props}></Icon>
