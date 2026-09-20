<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u84h5fbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u84h5fbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:milestone" {...props}></Icon>
