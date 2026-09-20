<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0h93f7on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l0h93f7on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:button" {...props}></Icon>
