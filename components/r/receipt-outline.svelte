<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh-pk_b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yh-pk_b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:receipt-outline" {...props}></Icon>
