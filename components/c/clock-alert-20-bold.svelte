<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwyep9bvy.css';
import '../../css/b/buhaxzbzx.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/i/i3tz2qbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwyep9bvy"/><path class="buhaxzbzx"/><path class="aqsnv9bnd"/><path class="i3tz2qbsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clock-alert-20-bold" {...props}></Icon>
