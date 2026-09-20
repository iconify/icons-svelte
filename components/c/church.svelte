<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws1o19b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ws1o19b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:church" {...props}></Icon>
