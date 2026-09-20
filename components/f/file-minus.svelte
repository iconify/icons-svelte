<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc91mi2ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cc91mi2ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:file-minus" {...props}></Icon>
