<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5za02bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c5za02bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:font-bold" {...props}></Icon>
