<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xedcedcye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xedcedcye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:floppy-disk-remix" {...props}></Icon>
