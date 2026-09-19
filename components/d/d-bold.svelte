<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8yegab2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k8yegab2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:d-bold" {...props}></Icon>
