<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phln6ib9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="phln6ib9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lu-zi-symbol" {...props}></Icon>
