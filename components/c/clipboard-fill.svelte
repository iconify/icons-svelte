<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezryhh6rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ezryhh6rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clipboard-fill" {...props}></Icon>
