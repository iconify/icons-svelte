<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu8uaebku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gu8uaebku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:copy-stroke-16" {...props}></Icon>
