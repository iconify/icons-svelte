<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv_-h5b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nv_-h5b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-chart-bar-16-solid" {...props}></Icon>
