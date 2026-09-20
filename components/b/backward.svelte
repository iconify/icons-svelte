<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h66lev3gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h66lev3gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:backward" {...props}></Icon>
