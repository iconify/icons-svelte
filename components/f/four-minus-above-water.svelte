<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk1emt_3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kk1emt_3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-minus-above-water" {...props}></Icon>
