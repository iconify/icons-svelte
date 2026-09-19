<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp2ifdcbr.css';
import '../../css/b/b2kor1dzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bp2ifdcbr"/><path class="b2kor1dzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:chat-dot-round" {...props}></Icon>
