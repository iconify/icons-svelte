<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj-22oqqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj-22oqqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-code-outline" {...props}></Icon>
