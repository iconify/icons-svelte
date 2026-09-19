<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x07p7ld2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x07p7ld2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:moviereelalt" {...props}></Icon>
