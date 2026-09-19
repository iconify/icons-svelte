<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k49s1-b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="k49s1-b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:checkboxalt" {...props}></Icon>
