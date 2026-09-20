<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eccxdteeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eccxdteeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:home-4-remix" {...props}></Icon>
