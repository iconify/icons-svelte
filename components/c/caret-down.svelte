<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq0_qkw9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gq0_qkw9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:caret-down" {...props}></Icon>
