<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzmz5dn5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tzmz5dn5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:depth-chart-solid" {...props}></Icon>
