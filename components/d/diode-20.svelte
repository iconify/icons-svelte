<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztcljccrf.css';
import '../../css/m/mk532_t7l.css';
import '../../css/l/lr4yiccjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ztcljccrf"/><path class="mk532_t7l"/><path class="lr4yiccjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diode-20" {...props}></Icon>
