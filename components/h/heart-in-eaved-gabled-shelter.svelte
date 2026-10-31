<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-k6ywuma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g-k6ywuma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-in-eaved-gabled-shelter" {...props}></Icon>
