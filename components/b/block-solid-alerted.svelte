<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5x3eeo5d.css';
import '../../css/u/uuexlx2yt.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid--alerted clr-i-solid-path-1--alerted o5x3eeo5d"/><path class="clr-i-alert clr-i-solid--alerted clr-i-solid-path-2--alerted uuexlx2yt"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:block-solid-alerted" {...props}></Icon>
