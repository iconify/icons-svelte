<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp2y9kbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cp2y9kbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:disc" {...props}></Icon>
