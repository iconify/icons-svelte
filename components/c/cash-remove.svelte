<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r91_16h3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r91_16h3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cash-remove" {...props}></Icon>
