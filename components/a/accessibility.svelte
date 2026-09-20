<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oneyfnauf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oneyfnauf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:accessibility" {...props}></Icon>
