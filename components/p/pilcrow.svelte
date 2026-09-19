<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pafx6bbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pafx6bbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pilcrow" {...props}></Icon>
