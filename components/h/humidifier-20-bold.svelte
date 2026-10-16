<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi9ki3f1j.css';
import '../../css/e/ek0sa8bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gi9ki3f1j"/><path class="ek0sa8bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidifier-20-bold" {...props}></Icon>
