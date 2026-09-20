<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh-ld3xeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="uh-ld3xeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lineicons-alt" {...props}></Icon>
