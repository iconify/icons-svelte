<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jklz1kt1b.css';
import '../../css/a/awbaqxbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jklz1kt1b"/><path class="awbaqxbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:password-pusher-dark" {...props}></Icon>
