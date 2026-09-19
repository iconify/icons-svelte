<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt893gged.css';
import '../../css/e/eg39dacou.css';
import '../../css/l/lorjk2lby.css';
import '../../css/r/rzeq_svbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt893gged"/><path class="eg39dacou"/><path class="lorjk2lby"/><path class="rzeq_svbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:clock2thirty" {...props}></Icon>
