<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l28ij0y1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l28ij0y1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:axis-lock" {...props}></Icon>
