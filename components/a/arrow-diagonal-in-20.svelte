<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9kqie5ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o9kqie5ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-diagonal-in-20" {...props}></Icon>
