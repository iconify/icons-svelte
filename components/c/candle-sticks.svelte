<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9l5qacpy.css';
import '../../css/t/t4a3_jblt.css';
import '../../css/y/ypjfbwbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9l5qacpy"/><path class="t4a3_jblt"/><path class="ypjfbwbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:candle-sticks" {...props}></Icon>
