<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8x-3xv9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x8x-3xv9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bag-suitcase-4-remix" {...props}></Icon>
