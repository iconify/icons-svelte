<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y05o7zjhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y05o7zjhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:computer-fill" {...props}></Icon>
