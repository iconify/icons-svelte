<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvp6asbse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvp6asbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:pill" {...props}></Icon>
