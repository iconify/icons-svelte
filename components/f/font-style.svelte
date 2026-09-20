<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd64akb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hd64akb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:font-style" {...props}></Icon>
