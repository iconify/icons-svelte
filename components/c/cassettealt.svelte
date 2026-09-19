<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3tthjk-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="x3tthjk-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cassettealt" {...props}></Icon>
