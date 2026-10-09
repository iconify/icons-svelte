<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0q12sb0a.css';
import '../../css/r/r4qnuebsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d0q12sb0a"/><path class="r4qnuebsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-octagon-20-bold" {...props}></Icon>
