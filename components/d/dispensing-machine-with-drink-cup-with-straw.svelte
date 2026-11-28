<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kex-dpb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kex-dpb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dispensing-machine-with-drink-cup-with-straw" {...props}></Icon>
