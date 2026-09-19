<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfhzld-us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nfhzld-us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:javascript" {...props}></Icon>
