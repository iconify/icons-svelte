<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blo0asbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="blo0asbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:printer-off" {...props}></Icon>
