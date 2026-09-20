<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckg-0r-5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ckg-0r-5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:link-2" {...props}></Icon>
