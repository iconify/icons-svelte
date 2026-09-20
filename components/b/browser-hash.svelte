<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1cm9oozd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z1cm9oozd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-hash" {...props}></Icon>
