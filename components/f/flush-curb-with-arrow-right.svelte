<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfk3dfb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vfk3dfb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flush-curb-with-arrow-right" {...props}></Icon>
