<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrgr0mbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lrgr0mbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:delta-chat-light" {...props}></Icon>
