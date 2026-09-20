<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4tw58c5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y4tw58c5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:link-1" {...props}></Icon>
