<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne6vqlbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ne6vqlbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:font-roman" {...props}></Icon>
