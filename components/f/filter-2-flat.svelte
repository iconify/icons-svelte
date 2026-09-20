<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfc3tf98d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wfc3tf98d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:filter-2-flat" {...props}></Icon>
