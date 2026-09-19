<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6zf4mfqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="u6zf4mfqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:python" {...props}></Icon>
