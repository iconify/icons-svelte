<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqznt3_qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hqznt3_qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:1-plus" {...props}></Icon>
