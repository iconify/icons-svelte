<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx040bc6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bx040bc6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluffychat-dark" {...props}></Icon>
