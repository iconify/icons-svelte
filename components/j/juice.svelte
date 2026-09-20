<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw1lpcl0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lw1lpcl0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:juice" {...props}></Icon>
