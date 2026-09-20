<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc5-3bbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xc5-3bbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:basket-check" {...props}></Icon>
