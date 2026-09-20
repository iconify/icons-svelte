<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1pjvgx8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u1pjvgx8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:component-2" {...props}></Icon>
