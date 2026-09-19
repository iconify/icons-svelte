<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flzxn06iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flzxn06iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bar-chart-2-fill" {...props}></Icon>
