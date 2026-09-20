<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loo_9-4ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="loo_9-4ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:json" {...props}></Icon>
