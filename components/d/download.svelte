<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke28hy4he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ke28hy4he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:download" {...props}></Icon>
