<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp8p9sznl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dp8p9sznl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:drawing-pin" {...props}></Icon>
