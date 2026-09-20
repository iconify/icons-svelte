<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy_jm2heq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uy_jm2heq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:envelope-open" {...props}></Icon>
