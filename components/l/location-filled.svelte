<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyj0qsyvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wyj0qsyvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:location-filled" {...props}></Icon>
