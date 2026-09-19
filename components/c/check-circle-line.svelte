<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngoo26b5w.css';
import '../../css/s/sgl6mzbwy.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ngoo26b5w"/><path class="clr-i-outline clr-i-outline-path-2 sgl6mzbwy"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:check-circle-line" {...props}></Icon>
