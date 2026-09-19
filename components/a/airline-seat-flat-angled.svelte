<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cckjnebfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":456,"height":384};
const content = `<path class="cckjnebfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-flat-angled" {...props}></Icon>
