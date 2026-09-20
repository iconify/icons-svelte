<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj8eh_udw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aj8eh_udw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:corner-bottom-left" {...props}></Icon>
