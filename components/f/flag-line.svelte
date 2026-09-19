<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzjhb4vdg.css';
import '../../css/n/naokebl4y.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 dzjhb4vdg"/><path class="clr-i-outline clr-i-outline-path-2 naokebl4y"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:flag-line" {...props}></Icon>
