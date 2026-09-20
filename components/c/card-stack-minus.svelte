<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-2stacov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n-2stacov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:card-stack-minus" {...props}></Icon>
