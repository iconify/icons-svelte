<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vezmvbbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vezmvbbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hospital-fill" {...props}></Icon>
