<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq6v1fb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6v1fb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-space-around-filled" {...props}></Icon>
