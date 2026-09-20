<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxkwrxb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cxkwrxb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:loop" {...props}></Icon>
