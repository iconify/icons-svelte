<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/expt5jbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="expt5jbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:checkbox" {...props}></Icon>
