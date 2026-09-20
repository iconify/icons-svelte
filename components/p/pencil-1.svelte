<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7k_bffrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w7k_bffrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:pencil-1" {...props}></Icon>
