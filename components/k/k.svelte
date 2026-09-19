<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1i_snb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="i1i_snb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:k" {...props}></Icon>
