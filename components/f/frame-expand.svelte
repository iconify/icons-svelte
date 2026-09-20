<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc71leb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nc71leb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:frame-expand" {...props}></Icon>
