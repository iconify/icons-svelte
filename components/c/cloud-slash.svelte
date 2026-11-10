<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrpc_ab1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrpc_ab1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-slash" {...props}></Icon>
