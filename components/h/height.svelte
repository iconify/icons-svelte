<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxcwjibbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hxcwjibbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:height" {...props}></Icon>
