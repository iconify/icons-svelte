<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo4eunb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo4eunb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:apple-filled" {...props}></Icon>
