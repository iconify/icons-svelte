<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzhgbf3_i.css';
import '../../css/o/o_os-tbha.css';
import '../../css/y/yk66m8x8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lzhgbf3_i"/><path class="o_os-tbha"/><path class="yk66m8x8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medal-48-bold" {...props}></Icon>
