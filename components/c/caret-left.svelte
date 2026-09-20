<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8ni4vjdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c8ni4vjdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:caret-left" {...props}></Icon>
