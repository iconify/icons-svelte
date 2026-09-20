<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fid0nsdib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fid0nsdib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:cast" {...props}></Icon>
