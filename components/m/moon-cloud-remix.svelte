<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6gfxwb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j6gfxwb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:moon-cloud-remix" {...props}></Icon>
