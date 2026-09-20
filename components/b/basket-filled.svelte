<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q93xk0bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q93xk0bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:basket-filled" {...props}></Icon>
