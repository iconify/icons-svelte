<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl6ft-bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl6ft-bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-sparkle-round" {...props}></Icon>
