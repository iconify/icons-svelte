<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4os67b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r4os67b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:hamburger" {...props}></Icon>
