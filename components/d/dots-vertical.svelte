<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzw393b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qzw393b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:dots-vertical" {...props}></Icon>
