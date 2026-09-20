<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v528_2bxm.css';
import '../../css/v/voocfbbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v528_2bxm"/><path class="voocfbbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:anchor-center-right-16" {...props}></Icon>
