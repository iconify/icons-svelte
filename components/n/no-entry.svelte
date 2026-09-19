<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt43qwwoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lt43qwwoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:no-entry" {...props}></Icon>
