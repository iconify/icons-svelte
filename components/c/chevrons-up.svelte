<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7h13bb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e7h13bb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:chevrons-up" {...props}></Icon>
