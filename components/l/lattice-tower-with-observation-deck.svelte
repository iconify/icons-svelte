<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0g3nabyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n0g3nabyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lattice-tower-with-observation-deck" {...props}></Icon>
