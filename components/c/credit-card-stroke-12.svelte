<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1420tb-x.css';
import '../../css/o/o2k0j_bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<rect class="d1420tb-x"/><path class="o2k0j_bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:credit-card-stroke-12" {...props}></Icon>
