<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1os0n7nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b1os0n7nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-access-2013-dark" {...props}></Icon>
