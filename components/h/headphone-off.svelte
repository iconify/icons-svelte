<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sleixublu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sleixublu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:headphone-off" {...props}></Icon>
