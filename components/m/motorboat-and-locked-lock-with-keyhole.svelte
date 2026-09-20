<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqhabybfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cqhabybfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorboat-and-locked-lock-with-keyhole" {...props}></Icon>
