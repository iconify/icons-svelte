<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pagw__b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pagw__b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chat-bubble-left-right" {...props}></Icon>
