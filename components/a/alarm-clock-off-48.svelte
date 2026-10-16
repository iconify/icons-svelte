<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5mhtjb5j.css';
import '../../css/l/lnepfmblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w5mhtjb5j"/><path class="lnepfmblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-off-48" {...props}></Icon>
