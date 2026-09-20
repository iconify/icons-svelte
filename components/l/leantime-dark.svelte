<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im55vabao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="im55vabao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:leantime-dark" {...props}></Icon>
