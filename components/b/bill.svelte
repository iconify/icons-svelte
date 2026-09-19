<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4xqot16e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="r4xqot16e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bill" {...props}></Icon>
