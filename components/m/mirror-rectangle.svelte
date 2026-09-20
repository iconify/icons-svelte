<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-bix9fdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bix9fdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mirror-rectangle" {...props}></Icon>
