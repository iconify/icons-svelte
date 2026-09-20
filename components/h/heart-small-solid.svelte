<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap_4y_bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ap_4y_bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:heart-small-solid" {...props}></Icon>
