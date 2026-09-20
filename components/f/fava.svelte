<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yktm7h6-w.css';
import '../../css/o/oc2ujn7ja.css';
import '../../css/c/cx-cwhw8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yktm7h6-w"/><path class="oc2ujn7ja"/><path class="cx-cwhw8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fava" {...props}></Icon>
