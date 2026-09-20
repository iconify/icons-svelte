<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um9ch0b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="um9ch0b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bolt" {...props}></Icon>
