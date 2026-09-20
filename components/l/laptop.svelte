<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll6i8wx_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ll6i8wx_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:laptop" {...props}></Icon>
