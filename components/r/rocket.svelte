<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4n9gkkjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4n9gkkjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:rocket" {...props}></Icon>
