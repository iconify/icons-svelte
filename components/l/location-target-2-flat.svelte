<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr8b3abzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nr8b3abzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:location-target-2-flat" {...props}></Icon>
