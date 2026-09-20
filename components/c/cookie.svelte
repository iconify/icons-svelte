<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyevrgjzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zyevrgjzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:cookie" {...props}></Icon>
