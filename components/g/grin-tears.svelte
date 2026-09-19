<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2fp4nqfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="u2fp4nqfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-tears" {...props}></Icon>
