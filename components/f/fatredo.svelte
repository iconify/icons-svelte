<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpi7wrb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="bpi7wrb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fatredo" {...props}></Icon>
