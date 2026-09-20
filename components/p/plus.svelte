<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjkvumbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tjkvumbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:plus" {...props}></Icon>
