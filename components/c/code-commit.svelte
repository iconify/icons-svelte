<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkbhw_5_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="hkbhw_5_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:code-commit" {...props}></Icon>
