<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drsxbb9iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drsxbb9iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-l-filled" {...props}></Icon>
