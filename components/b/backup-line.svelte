<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf9v9teof.css';
import '../../css/s/skxfee1fo.css';
import '../../css/b/bmdiq6b8t.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 lf9v9teof"/><path class="clr-i-outline clr-i-outline-path-2 skxfee1fo"/><path class="bmdiq6b8t clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:backup-line" {...props}></Icon>
