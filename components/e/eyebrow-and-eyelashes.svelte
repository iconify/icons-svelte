<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi_56x-la.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oi_56x-la"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eyebrow-and-eyelashes" {...props}></Icon>
