<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tylrpc4_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tylrpc4_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:connected" {...props}></Icon>
