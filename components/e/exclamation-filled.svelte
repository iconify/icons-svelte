<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glxxy053g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="glxxy053g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:exclamation-filled" {...props}></Icon>
