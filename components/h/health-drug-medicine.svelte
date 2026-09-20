<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4hh0wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x4hh0wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-drug-medicine" {...props}></Icon>
