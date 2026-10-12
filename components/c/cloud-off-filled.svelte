<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvtxu9bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvtxu9bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-off-filled" {...props}></Icon>
