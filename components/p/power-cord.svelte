<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s53j2rtlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s53j2rtlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:power-cord" {...props}></Icon>
