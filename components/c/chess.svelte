<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7kkpvbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7kkpvbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chess" {...props}></Icon>
