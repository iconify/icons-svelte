<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzlx0ujqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="gzlx0ujqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-reopened" {...props}></Icon>
