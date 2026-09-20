<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s84_ybbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s84_ybbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:e-bike-line" {...props}></Icon>
