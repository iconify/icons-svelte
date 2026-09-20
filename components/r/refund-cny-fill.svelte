<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn6i_fowy.css';
import '../../css/a/adhtr2bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn6i_fowy"/><path class="adhtr2bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refund-cny-fill" {...props}></Icon>
