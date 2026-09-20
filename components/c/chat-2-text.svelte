<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc5uqub2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sc5uqub2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chat-2-text" {...props}></Icon>
