<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az03b6bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="az03b6bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ebay" {...props}></Icon>
