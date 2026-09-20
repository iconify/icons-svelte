<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2d8-qbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f2d8-qbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-finger-drag-vertical-remix" {...props}></Icon>
