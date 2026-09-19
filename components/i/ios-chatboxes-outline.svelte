<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejq_vxbcb.css';
import '../../css/q/qcygcjg0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ejq_vxbcb"/><path class="qcygcjg0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-chatboxes-outline" {...props}></Icon>
