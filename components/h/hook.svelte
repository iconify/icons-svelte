<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq3fydbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pq3fydbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hook" {...props}></Icon>
