<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbpijbb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lbpijbb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:production-service" {...props}></Icon>
