<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9cdcizyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h9cdcizyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:display-alt" {...props}></Icon>
