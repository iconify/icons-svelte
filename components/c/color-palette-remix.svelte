<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orrp5pbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orrp5pbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:color-palette-remix" {...props}></Icon>
