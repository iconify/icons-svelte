<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkezptote.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zkezptote"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:location-compass-1-remix" {...props}></Icon>
