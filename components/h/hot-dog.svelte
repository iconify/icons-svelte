<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugbis8cfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ugbis8cfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hot-dog" {...props}></Icon>
