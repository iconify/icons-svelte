<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/hmd6rr.css';
import '../../css/p/pfsmgv.css';
import '../../css/z/zahr3u.css';
import '../../css/s/so-from-70.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hmd6rr"/><path class="a0m25c pfsmgv"/><path class="a0m25c zahr3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chat-alert" {...props}></Icon>
