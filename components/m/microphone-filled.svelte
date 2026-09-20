<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8mzs5o2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o8mzs5o2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:microphone-filled" {...props}></Icon>
