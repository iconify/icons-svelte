<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slqqs4bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="slqqs4bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:enter-full-screen" {...props}></Icon>
