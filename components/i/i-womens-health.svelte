<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1n-zwboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="i1n-zwboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-womens-health" {...props}></Icon>
