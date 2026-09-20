<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8eq9ybzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n8eq9ybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:image-location-remix" {...props}></Icon>
