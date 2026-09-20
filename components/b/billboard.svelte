<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5cc2kldq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b5cc2kldq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:billboard" {...props}></Icon>
