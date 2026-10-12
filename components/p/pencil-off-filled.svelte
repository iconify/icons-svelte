<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3bt1acyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3bt1acyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pencil-off-filled" {...props}></Icon>
