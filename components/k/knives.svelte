<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5o0kxbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f5o0kxbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:knives" {...props}></Icon>
