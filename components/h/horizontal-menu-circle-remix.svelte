<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap42-obbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ap42-obbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:horizontal-menu-circle-remix" {...props}></Icon>
