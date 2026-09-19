<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dndr6q80t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dndr6q80t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:circle" {...props}></Icon>
