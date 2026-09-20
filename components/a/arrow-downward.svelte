<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3bc0lb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="q3bc0lb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-downward" {...props}></Icon>
