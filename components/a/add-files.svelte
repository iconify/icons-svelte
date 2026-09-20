<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhllcmz3q.css';
import '../../css/g/g11id0bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fhllcmz3q"/><path class="g11id0bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:add-files" {...props}></Icon>
