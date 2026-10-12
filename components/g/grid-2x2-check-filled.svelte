<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa5vtea9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa5vtea9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:grid-2x2-check-filled" {...props}></Icon>
