<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e49y6d30i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e49y6d30i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-book-above-outstretched-hand" {...props}></Icon>
