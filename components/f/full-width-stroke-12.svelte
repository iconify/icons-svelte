<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdblp_bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bdblp_bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:full-width-stroke-12" {...props}></Icon>
