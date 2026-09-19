<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oox843b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="oox843b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:document-chart-bar" {...props}></Icon>
