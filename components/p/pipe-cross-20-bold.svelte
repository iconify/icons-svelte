<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekeuohc1r.css';
import '../../css/s/su_ej-b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ekeuohc1r"/><path class="su_ej-b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-cross-20-bold" {...props}></Icon>
