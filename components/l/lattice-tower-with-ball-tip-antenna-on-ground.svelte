<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqhiw328v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kqhiw328v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lattice-tower-with-ball-tip-antenna-on-ground" {...props}></Icon>
