<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkjfiabpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vkjfiabpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:download" {...props}></Icon>
