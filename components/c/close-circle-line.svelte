<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_wq8_b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_wq8_b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:close-circle-line" {...props}></Icon>
