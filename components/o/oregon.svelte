<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhknwb6nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yhknwb6nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:oregon" {...props}></Icon>
