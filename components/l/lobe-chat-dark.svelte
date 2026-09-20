<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jstim82hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jstim82hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lobe-chat-dark" {...props}></Icon>
