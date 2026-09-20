<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2zekxdxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v2zekxdxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:instagram-logo" {...props}></Icon>
