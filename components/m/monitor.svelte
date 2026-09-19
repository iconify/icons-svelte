<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9kl6h36h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k9kl6h36h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:monitor" {...props}></Icon>
