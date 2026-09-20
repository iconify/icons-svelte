<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z474r-67j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z474r-67j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:minus" {...props}></Icon>
