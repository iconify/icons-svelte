<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_z-q-bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_z-q-bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:line-chart-line" {...props}></Icon>
