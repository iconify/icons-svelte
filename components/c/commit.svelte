<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_69oybqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l_69oybqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:commit" {...props}></Icon>
