<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ninr9tbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ninr9tbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-like-outline" {...props}></Icon>
