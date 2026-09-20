<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1trvbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq1trvbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:chevron-down" {...props}></Icon>
