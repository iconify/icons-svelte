<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao-mrdbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ao-mrdbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-right-20" {...props}></Icon>
