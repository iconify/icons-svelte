<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0s_u7b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u0s_u7b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:crown" {...props}></Icon>
