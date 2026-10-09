<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp3cjxxjv.css';
import '../../css/x/xranyficx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tp3cjxxjv"/><path class="xranyficx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-open-20-bold" {...props}></Icon>
