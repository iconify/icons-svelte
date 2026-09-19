<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp8c-eb8i.css';
import '../../css/h/hid2coqpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="fp8c-eb8i"/><path class="hid2coqpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:price-tags" {...props}></Icon>
