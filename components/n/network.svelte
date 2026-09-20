<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwfe6tbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="gwfe6tbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:network" {...props}></Icon>
