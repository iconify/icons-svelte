<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1vs7vb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1vs7vb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cigarette-filled" {...props}></Icon>
