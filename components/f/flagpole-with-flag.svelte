<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd86ys90j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sd86ys90j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flagpole-with-flag" {...props}></Icon>
