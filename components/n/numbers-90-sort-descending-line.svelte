<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc9b7dblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc9b7dblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-90-sort-descending-line" {...props}></Icon>
