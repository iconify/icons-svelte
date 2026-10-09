<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7p6popon.css';
import '../../css/u/uzzfsfvad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r7p6popon"/><path class="uzzfsfvad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-20" {...props}></Icon>
