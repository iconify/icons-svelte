<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfz6qsjee.css';
import '../../css/c/cq_7-dbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfz6qsjee"/><path clip-rule="evenodd" class="cq_7-dbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-arrow-bold-duotone" {...props}></Icon>
