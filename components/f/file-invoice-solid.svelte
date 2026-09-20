<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzkptq_9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fzkptq_9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-invoice-solid" {...props}></Icon>
