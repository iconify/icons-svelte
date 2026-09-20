<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bunby8b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bunby8b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-scale-2" {...props}></Icon>
