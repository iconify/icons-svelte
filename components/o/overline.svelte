<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w14e7yb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w14e7yb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:overline" {...props}></Icon>
