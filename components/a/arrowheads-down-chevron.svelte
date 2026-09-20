<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl9y0jbvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gl9y0jbvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-chevron" {...props}></Icon>
