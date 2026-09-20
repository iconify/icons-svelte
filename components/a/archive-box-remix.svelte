<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9zih83im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o9zih83im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:archive-box-remix" {...props}></Icon>
