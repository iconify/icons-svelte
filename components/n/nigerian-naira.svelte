<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihu8-ii_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihu8-ii_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:nigerian-naira" {...props}></Icon>
