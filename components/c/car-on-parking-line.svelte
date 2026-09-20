<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjet1jbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kjet1jbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-on-parking-line" {...props}></Icon>
