<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjmdefyhd.css';
import '../../css/k/k4tc3yb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":277};
const content = `<path class="xjmdefyhd"/><path class="k4tc3yb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:redwoodjs" {...props}></Icon>
