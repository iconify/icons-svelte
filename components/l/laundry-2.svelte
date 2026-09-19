<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyd_bcid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyyd_bcid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:laundry-2" {...props}></Icon>
