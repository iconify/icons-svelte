<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diykwy11w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="diykwy11w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:rotate-counter-clockwise" {...props}></Icon>
