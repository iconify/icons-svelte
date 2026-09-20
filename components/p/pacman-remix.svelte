<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6j3f6b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e6j3f6b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pacman-remix" {...props}></Icon>
