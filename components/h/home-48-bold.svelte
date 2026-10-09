<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh809gb4r.css';
import '../../css/p/pahc4sbmv.css';
import '../../css/y/yvkfxeizw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zh809gb4r"/><path class="pahc4sbmv"/><path class="yvkfxeizw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:home-48-bold" {...props}></Icon>
