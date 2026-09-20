<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6t-qx8yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j6t-qx8yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-new" {...props}></Icon>
