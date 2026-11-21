<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieszopq_p.css';
import '../../css/u/ua2r80buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ieszopq_p"/><path class="ua2r80buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-rain-wind-filled" {...props}></Icon>
