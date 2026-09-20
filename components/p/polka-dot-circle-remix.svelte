<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfatfab1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gfatfab1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:polka-dot-circle-remix" {...props}></Icon>
