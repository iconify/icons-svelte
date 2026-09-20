<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbn7s3nsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vbn7s3nsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:newspaper-solid" {...props}></Icon>
