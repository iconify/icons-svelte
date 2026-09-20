<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ex51bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e3ex51bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:network-remix" {...props}></Icon>
