<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx9jrebeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dx9jrebeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:inbox-tray-1-remix" {...props}></Icon>
