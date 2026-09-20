<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjxi2l7co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xjxi2l7co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cleaver" {...props}></Icon>
