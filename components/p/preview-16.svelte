<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqykx7ber.css';
import '../../css/a/ayrt9cq7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oqykx7ber"/><path clip-rule="evenodd" class="ayrt9cq7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:preview-16" {...props}></Icon>
