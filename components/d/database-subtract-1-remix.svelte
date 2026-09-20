<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlld-vbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vlld-vbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-subtract-1-remix" {...props}></Icon>
