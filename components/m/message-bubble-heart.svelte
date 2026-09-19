<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drpo4ybcc.css';
import '../../css/w/w5v5asbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drpo4ybcc"/><path class="w5v5asbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-heart" {...props}></Icon>
