<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4min-bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m4min-bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:linux-namespace" {...props}></Icon>
