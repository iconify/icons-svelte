<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4yfsnzeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="s4yfsnzeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:italic" {...props}></Icon>
