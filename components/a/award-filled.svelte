<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbtb8tbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbtb8tbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:award-filled" {...props}></Icon>
