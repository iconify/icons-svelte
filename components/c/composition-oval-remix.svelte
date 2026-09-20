<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb0xdf74c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wb0xdf74c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:composition-oval-remix" {...props}></Icon>
