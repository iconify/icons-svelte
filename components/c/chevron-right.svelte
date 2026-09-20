<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k15v96bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k15v96bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:chevron-right" {...props}></Icon>
