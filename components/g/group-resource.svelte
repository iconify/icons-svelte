<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2iip6b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x2iip6b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:group-resource" {...props}></Icon>
