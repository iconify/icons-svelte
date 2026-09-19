<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa740y-ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wa740y-ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:chat-bubble-bottom-center-text" {...props}></Icon>
