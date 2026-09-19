<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol-p9lb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ol-p9lb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-left-20-solid" {...props}></Icon>
