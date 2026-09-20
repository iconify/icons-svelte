<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r7bbwk2ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r7bbwk2ui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:justify-start" {...props}></Icon>
