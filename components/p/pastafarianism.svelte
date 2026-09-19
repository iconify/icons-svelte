<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr4px3b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lr4px3b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:pastafarianism" {...props}></Icon>
