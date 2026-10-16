<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpapdbc8v.css';
import '../../css/y/yeva_mbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lpapdbc8v"/><path class="yeva_mbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:immersion-heater-48" {...props}></Icon>
