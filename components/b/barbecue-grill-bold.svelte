<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nga6i44tb.css';
import '../../css/r/r7yb4cbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nga6i44tb"/><path class="r7yb4cbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:barbecue-grill-bold" {...props}></Icon>
