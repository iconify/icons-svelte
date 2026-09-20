<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owo7x-n0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="owo7x-n0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lift-disability-remix" {...props}></Icon>
