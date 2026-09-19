<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgero7bbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="sgero7bbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:die-three" {...props}></Icon>
