<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omq3peb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="omq3peb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:library-16" {...props}></Icon>
