<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5v5asbue.css';
import '../../css/d/djipz6cyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5v5asbue"/><path class="djipz6cyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-star" {...props}></Icon>
