<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lazlouosg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="lazlouosg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:crossref" {...props}></Icon>
