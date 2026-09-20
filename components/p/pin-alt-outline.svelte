<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8lln2bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y8lln2bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pin-alt-outline" {...props}></Icon>
