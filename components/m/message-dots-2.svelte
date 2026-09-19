<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p56h_bbeb.css';
import '../../css/b/bhtd76b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p56h_bbeb"/><path class="bhtd76b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-dots-2" {...props}></Icon>
