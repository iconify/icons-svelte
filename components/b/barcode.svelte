<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozxot9bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ozxot9bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:barcode" {...props}></Icon>
