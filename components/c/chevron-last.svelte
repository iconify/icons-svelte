<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwv11hbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwv11hbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevron-last" {...props}></Icon>
