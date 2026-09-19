<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbu8ekbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mbu8ekbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:file-x" {...props}></Icon>
