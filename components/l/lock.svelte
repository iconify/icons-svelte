<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6mgy9awu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":582,"height":1000};
const content = `<path class="r6mgy9awu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:lock" {...props}></Icon>
