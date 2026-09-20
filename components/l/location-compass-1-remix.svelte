<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6p4lbbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h6p4lbbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:location-compass-1-remix" {...props}></Icon>
