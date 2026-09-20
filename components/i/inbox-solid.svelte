<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvuoqfmio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gvuoqfmio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:inbox-solid" {...props}></Icon>
