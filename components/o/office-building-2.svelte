<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x03ow4b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x03ow4b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:office-building-2" {...props}></Icon>
