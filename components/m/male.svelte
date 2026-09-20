<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuh6h7j6z.css';
import '../../css/x/xfomdp99f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vuh6h7j6z"/><circle class="xfomdp99f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:male" {...props}></Icon>
