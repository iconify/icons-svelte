<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc9_1yu8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oc9_1yu8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-reverse-stroke-12" {...props}></Icon>
