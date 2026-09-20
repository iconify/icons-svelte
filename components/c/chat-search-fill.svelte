<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmpu4c7qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmpu4c7qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-search-fill" {...props}></Icon>
