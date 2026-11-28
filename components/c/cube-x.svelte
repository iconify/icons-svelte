<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e53y4lb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e53y4lb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cube-x" {...props}></Icon>
