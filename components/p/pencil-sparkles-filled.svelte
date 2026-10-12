<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb_pv7qoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sb_pv7qoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pencil-sparkles-filled" {...props}></Icon>
