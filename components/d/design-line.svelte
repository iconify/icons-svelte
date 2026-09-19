<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9zjpsbxq.css';
import '../../css/i/izomx4vfd.css';
import '../../css/r/rra0q9q9g.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 d9zjpsbxq"/><path class="clr-i-outline clr-i-outline-path-2 izomx4vfd"/><path class="clr-i-outline clr-i-outline-path-3 rra0q9q9g"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:design-line" {...props}></Icon>
