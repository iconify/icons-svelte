<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys6kqr79s.css';
import '../../css/b/bp242uqss.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ys6kqr79s"/><path class="bp242uqss clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:dot-circle-line" {...props}></Icon>
