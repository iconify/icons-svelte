<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6sj6mbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e6sj6mbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:bookmark" {...props}></Icon>
