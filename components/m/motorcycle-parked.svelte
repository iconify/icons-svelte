<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euksa8bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="euksa8bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:motorcycle-parked" {...props}></Icon>
