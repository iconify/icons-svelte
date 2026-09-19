<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1c49rb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l1c49rb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:goldenline" {...props}></Icon>
