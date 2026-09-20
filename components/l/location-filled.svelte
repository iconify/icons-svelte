<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4s149y6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4s149y6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:location-filled" {...props}></Icon>
