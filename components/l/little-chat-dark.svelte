<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9-4b0rca.css';
import '../../css/l/lrv75jbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9-4b0rca"/><path class="lrv75jbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:little-chat-dark" {...props}></Icon>
