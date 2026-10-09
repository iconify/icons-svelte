<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvxc71wgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cvxc71wgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-off-48-bold" {...props}></Icon>
