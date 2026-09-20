<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5he1-qhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e5he1-qhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:file" {...props}></Icon>
