<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beg3fv-xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="beg3fv-xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-check-outline" {...props}></Icon>
