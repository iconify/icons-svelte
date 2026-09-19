<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxu0irn3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mxu0irn3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:minus" {...props}></Icon>
