<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pokp8ab5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pokp8ab5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrows-up-to-line" {...props}></Icon>
