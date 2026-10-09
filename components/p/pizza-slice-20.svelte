<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_g30-bhd.css';
import '../../css/c/ce0hw2blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z_g30-bhd"/><path class="ce0hw2blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pizza-slice-20" {...props}></Icon>
