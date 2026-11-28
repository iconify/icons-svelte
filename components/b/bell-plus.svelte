<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reywt300r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="reywt300r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bell-plus" {...props}></Icon>
