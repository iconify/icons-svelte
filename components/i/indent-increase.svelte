<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvdyix59y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvdyix59y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:indent-increase" {...props}></Icon>
