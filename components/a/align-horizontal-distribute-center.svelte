<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6c46zggq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6c46zggq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-distribute-center" {...props}></Icon>
