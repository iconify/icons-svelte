<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxnfo63mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kxnfo63mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-from-wide-rectangle-outline" {...props}></Icon>
