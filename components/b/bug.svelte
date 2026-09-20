<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw5ivpiyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jw5ivpiyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bug" {...props}></Icon>
