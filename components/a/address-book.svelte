<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j90dtx-pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j90dtx-pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:address-book" {...props}></Icon>
