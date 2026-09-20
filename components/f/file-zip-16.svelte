<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox4mohbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ox4mohbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-zip-16" {...props}></Icon>
