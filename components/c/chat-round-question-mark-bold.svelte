<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcsb5qxsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcsb5qxsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-question-mark-bold" {...props}></Icon>
