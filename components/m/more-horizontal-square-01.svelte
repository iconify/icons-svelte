<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_rht5bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_rht5bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-horizontal-square-01" {...props}></Icon>
