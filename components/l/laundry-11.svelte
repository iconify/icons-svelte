<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k40_dxbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="k40_dxbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:laundry-11" {...props}></Icon>
