<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1c8tbc2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x1c8tbc2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:alt-remix" {...props}></Icon>
