<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbvg1o4cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tbvg1o4cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loader-2-48-bold" {...props}></Icon>
