<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_v5ysu5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o_v5ysu5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:phone" {...props}></Icon>
