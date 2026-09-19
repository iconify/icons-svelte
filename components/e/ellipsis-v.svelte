<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxz5dobuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":1408};
const content = `<path class="oxz5dobuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ellipsis-v" {...props}></Icon>
