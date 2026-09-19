<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-4if6c6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="n-4if6c6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:money-off" {...props}></Icon>
