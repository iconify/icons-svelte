<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_8ytmbdv.css';
import '../../css/n/nicoetbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_8ytmbdv"/><path class="nicoetbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-pie-filled" {...props}></Icon>
