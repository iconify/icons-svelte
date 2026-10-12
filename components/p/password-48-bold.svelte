<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiqj48bop.css';
import '../../css/a/ahgdhlcfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yiqj48bop"/><path class="ahgdhlcfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:password-48-bold" {...props}></Icon>
