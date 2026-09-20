<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu58r9bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vu58r9bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hash" {...props}></Icon>
