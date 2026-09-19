<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgu0l2-ex.css';
import '../../css/b/b54bhv41g.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted zgu0l2-ex"/><path class="b54bhv41g clr-i-solid--alerted clr-i-solid-path-2--alerted"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-3--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:date-solid-alerted" {...props}></Icon>
