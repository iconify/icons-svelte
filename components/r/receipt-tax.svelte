<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alm8q0_fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="alm8q0_fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:receipt-tax" {...props}></Icon>
