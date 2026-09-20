<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3_b9ib7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i3_b9ib7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rocket" {...props}></Icon>
