<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn5-p75tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mn5-p75tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-baseball-batting" {...props}></Icon>
