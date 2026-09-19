<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp2ifdcbr.css';
import '../../css/d/dn0-kucri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bp2ifdcbr"/><path class="dn0-kucri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:chat-line-round" {...props}></Icon>
