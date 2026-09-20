<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8c084gqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d8c084gqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:cloud-network-1" {...props}></Icon>
