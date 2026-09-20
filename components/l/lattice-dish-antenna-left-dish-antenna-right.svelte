<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-7hzubuy.css';
import '../../css/m/m2p7gebqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-7hzubuy"/><path class="m2p7gebqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lattice-dish-antenna-left-dish-antenna-right" {...props}></Icon>
