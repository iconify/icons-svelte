<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvoodkb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvoodkb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-plus-round" {...props}></Icon>
