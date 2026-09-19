<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7bk8s24b.css';
import '../../css/c/cnc3b_b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7bk8s24b"/><path clip-rule="evenodd" class="cnc3b_b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:invoice-outline" {...props}></Icon>
