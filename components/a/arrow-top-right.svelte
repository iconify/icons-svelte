<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6x6wlb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o6x6wlb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-top-right" {...props}></Icon>
