<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbxan1-lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pbxan1-lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up-right-chevron" {...props}></Icon>
