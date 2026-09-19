<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9pq9_1gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="e9pq9_1gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillek" {...props}></Icon>
