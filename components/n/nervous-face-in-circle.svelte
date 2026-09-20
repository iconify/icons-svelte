<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcn09ub7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fcn09ub7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:nervous-face-in-circle" {...props}></Icon>
