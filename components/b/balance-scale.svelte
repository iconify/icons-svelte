<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-3desbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-3desbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:balance-scale" {...props}></Icon>
