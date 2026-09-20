<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl4teebwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sl4teebwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-right" {...props}></Icon>
