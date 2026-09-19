<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6u46ccfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j6u46ccfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:leaf" {...props}></Icon>
