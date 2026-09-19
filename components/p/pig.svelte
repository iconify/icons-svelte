<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acxms6bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="acxms6bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pig" {...props}></Icon>
