<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi0yuo35w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fi0yuo35w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:monitor" {...props}></Icon>
