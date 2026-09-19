<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg690wp1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="qg690wp1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:bell" {...props}></Icon>
