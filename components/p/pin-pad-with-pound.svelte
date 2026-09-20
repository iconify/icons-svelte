<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb711uq0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qb711uq0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-pound" {...props}></Icon>
