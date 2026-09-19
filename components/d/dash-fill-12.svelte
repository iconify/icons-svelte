<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg-rq_txf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rg-rq_txf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dash-fill-12" {...props}></Icon>
