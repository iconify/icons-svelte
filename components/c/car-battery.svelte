<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj_2pgc9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lj_2pgc9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-battery" {...props}></Icon>
