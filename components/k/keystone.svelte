<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v07i1dbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v07i1dbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:keystone" {...props}></Icon>
