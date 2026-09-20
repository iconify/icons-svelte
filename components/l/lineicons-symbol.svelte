<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9a3omb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="z9a3omb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lineicons-symbol" {...props}></Icon>
