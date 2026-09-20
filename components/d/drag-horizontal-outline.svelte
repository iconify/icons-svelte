<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-91d64oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r-91d64oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:drag-horizontal-outline" {...props}></Icon>
