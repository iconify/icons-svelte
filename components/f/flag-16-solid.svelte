<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gum74vxer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gum74vxer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:flag-16-solid" {...props}></Icon>
