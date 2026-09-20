<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb3zy6b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wb3zy6b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:link-none-1" {...props}></Icon>
