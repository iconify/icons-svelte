<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj5drf1ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xj5drf1ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:highlight" {...props}></Icon>
